<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkbgrjdet.css';
import '../../css/l/l9ksdwb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkbgrjdet"/><path clip-rule="evenodd" class="l9ksdwb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:side-peek" {...props}></Icon>
