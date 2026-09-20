<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6g3pqe8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6g3pqe8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:widget-ppf" {...props}></Icon>
