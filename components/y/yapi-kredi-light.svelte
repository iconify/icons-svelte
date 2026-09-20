<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os7-1hbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1548,"height":786};
const content = `<path class="os7-1hbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yapi-kredi-light" {...props}></Icon>
