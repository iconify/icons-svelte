<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7j255bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7j255bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:user-refresh" {...props}></Icon>
