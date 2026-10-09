<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxd6jfy2h.css';
import '../../css/c/chzkkvbwn.css';
import '../../css/k/k2xeydb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zxd6jfy2h"/><path class="chzkkvbwn"/><path class="k2xeydb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toolbox-20" {...props}></Icon>
