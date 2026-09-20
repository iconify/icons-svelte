<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2oxshb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e2oxshb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:semaphore-ui-dark" {...props}></Icon>
