<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5i-kqbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m5i-kqbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:youtube-with-circle" {...props}></Icon>
