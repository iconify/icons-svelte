<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrml8r0nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zrml8r0nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-google" {...props}></Icon>
