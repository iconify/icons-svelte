<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q29c6fb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q29c6fb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:tripadvisor" {...props}></Icon>
