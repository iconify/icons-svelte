<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihkyds_0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ihkyds_0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:upload-track" {...props}></Icon>
