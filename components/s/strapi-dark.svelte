<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru_rc6bbb.css';
import '../../css/k/ktli5dbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ru_rc6bbb"/><path class="ktli5dbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:strapi-dark" {...props}></Icon>
