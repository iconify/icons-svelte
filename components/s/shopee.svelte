<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5snt8_wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5snt8_wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:shopee" {...props}></Icon>
