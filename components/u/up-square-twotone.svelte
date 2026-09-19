<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc8-4tb2b.css';
import '../../css/r/rhd644bpf.css';
import '../../css/i/iqhuk7_4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gc8-4tb2b"/><path class="rhd644bpf"/><path class="iqhuk7_4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:up-square-twotone" {...props}></Icon>
