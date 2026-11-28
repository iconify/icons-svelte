<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhj9y3icm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhj9y3icm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shopping-bag-solid" {...props}></Icon>
