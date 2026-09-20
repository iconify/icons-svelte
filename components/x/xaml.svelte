<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aef3ixbes.css';
import '../../css/c/c2c3p-b5s.css';
import '../../css/z/zm33ygepl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aef3ixbes"/><path class="c2c3p-b5s"/><path class="zm33ygepl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:xaml" {...props}></Icon>
