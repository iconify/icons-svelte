<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjo6bv0or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":443,"height":512};
const content = `<path class="qjo6bv0or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:sequelize" {...props}></Icon>
