<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etl048b3a.css';
import '../../css/a/alhm_84rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="etl048b3a"/><path class="alhm_84rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:route-20-bold" {...props}></Icon>
