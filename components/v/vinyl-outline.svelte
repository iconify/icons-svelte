<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hloqtyxnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hloqtyxnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:vinyl-outline" {...props}></Icon>
