<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7z1k8tcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a7z1k8tcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:symbol-male" {...props}></Icon>
