<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7zn-235y.css';
import '../../css/b/banrz7b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7zn-235y"/><path clip-rule="evenodd" class="banrz7b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:webcam-bold" {...props}></Icon>
