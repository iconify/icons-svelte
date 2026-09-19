<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnl0g-byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bnl0g-byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:vertical-align-bottom-outline" {...props}></Icon>
