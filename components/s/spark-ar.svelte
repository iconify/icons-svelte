<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nko8i8blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nko8i8blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:spark-ar" {...props}></Icon>
