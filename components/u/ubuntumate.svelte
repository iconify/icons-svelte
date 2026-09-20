<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atg1-5blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atg1-5blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ubuntumate" {...props}></Icon>
