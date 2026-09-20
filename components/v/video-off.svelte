<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e28z0dvfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e28z0dvfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-off" {...props}></Icon>
