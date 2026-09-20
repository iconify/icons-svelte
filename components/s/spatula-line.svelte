<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixa2rjbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixa2rjbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:spatula-line" {...props}></Icon>
