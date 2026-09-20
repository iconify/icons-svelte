<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbpbqzb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="gbpbqzb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:unlink-2-angular-eft" {...props}></Icon>
