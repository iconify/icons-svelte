<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0wlenb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h0wlenb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:share-alt-outline" {...props}></Icon>
