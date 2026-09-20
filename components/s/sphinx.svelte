<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxst_t7um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxst_t7um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:sphinx" {...props}></Icon>
