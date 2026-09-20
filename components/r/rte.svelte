<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqxvu2bqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqxvu2bqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rte" {...props}></Icon>
