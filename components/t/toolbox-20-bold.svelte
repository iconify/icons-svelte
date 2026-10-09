<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvyjh5a_p.css';
import '../../css/g/g95ma61en.css';
import '../../css/s/s4i4qlbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hvyjh5a_p"/><path class="g95ma61en"/><path class="s4i4qlbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toolbox-20-bold" {...props}></Icon>
