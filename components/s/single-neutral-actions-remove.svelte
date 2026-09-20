<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3lstkfqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3lstkfqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-neutral-actions-remove" {...props}></Icon>
