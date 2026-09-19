<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaa10iz8w.css';
import '../../css/i/is07s5r9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iaa10iz8w"/><path class="is07s5r9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:sliders-twotone" {...props}></Icon>
