<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alobnivwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1548,"height":786};
const content = `<path class="alobnivwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yapi-kredi-dark" {...props}></Icon>
