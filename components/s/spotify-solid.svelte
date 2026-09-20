<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd5glhbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qd5glhbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:spotify-solid" {...props}></Icon>
