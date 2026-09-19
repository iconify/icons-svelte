<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe6cqt_uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pe6cqt_uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:slack-outlined" {...props}></Icon>
