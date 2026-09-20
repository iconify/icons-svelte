<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln2yt9bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ln2yt9bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:unlock-alt-fill" {...props}></Icon>
