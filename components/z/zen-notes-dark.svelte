<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ive8xobqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ive8xobqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zen-notes-dark" {...props}></Icon>
