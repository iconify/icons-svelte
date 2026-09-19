<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzl7znbzk.css';
import '../../css/u/uqsh6ibhf.css';
import '../../css/p/pr87757ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qzl7znbzk"/><path class="uqsh6ibhf"/><circle class="pr87757ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:unlock" {...props}></Icon>
