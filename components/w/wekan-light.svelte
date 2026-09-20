<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwh_-fbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iwh_-fbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wekan-light" {...props}></Icon>
