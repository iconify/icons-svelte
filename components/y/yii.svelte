<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrtid2b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zrtid2b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:yii" {...props}></Icon>
