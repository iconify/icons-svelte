<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o27bx7bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o27bx7bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:thumbs-up" {...props}></Icon>
