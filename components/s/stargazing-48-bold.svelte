<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqy6lhb1f.css';
import '../../css/o/oz0-7c0kb.css';
import '../../css/n/n2f3vcc0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jqy6lhb1f"/><path class="oz0-7c0kb"/><path class="n2f3vcc0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stargazing-48-bold" {...props}></Icon>
