<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojovl0byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojovl0byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:trading-pattern-up" {...props}></Icon>
