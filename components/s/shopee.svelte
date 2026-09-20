<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr8mzjbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr8mzjbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:shopee" {...props}></Icon>
