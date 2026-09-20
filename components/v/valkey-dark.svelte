<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4djgccro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v4djgccro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:valkey-dark" {...props}></Icon>
