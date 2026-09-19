<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkmbsbbqu.css';
import '../../css/k/kb1ytkvcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jkmbsbbqu"/><path class="kb1ytkvcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:vip" {...props}></Icon>
