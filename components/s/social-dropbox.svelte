<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzksm6bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qzksm6bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-dropbox" {...props}></Icon>
