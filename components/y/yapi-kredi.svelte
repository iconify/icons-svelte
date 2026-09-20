<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceemambxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1548,"height":786};
const content = `<path class="ceemambxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:yapi-kredi" {...props}></Icon>
