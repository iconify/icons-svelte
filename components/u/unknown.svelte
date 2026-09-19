<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6riqxspa.css';
import '../../css/o/o2503rbla.css';
import '../../css/y/yti26qboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="v6riqxspa"/><path class="o2503rbla"/><path class="yti26qboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:unknown" {...props}></Icon>
