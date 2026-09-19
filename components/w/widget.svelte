<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp7hdwqxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp7hdwqxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:widget" {...props}></Icon>
