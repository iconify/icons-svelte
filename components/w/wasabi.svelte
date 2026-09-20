<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty_1w39kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty_1w39kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wasabi" {...props}></Icon>
