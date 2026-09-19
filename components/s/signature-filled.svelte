<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y35j6lhfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y35j6lhfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:signature-filled" {...props}></Icon>
