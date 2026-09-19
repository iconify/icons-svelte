<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h482tac2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h482tac2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:tablet-filled" {...props}></Icon>
