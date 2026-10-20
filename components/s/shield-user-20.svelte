<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukrge3umx.css';
import '../../css/a/aavhnbyqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ukrge3umx"/><path class="aavhnbyqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-user-20" {...props}></Icon>
