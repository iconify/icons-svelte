<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spf182b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="spf182b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shield-stroke-20" {...props}></Icon>
