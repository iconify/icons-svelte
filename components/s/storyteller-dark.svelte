<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibzarcmis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ibzarcmis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storyteller-dark" {...props}></Icon>
