<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdc2ltdiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tdc2ltdiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-github" {...props}></Icon>
