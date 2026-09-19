<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5w6ywn1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="t5w6ywn1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:usergroup-delete" {...props}></Icon>
