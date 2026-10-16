<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5j847bee.css';
import '../../css/p/pr4dqmbxn.css';
import '../../css/n/n_d0zwbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w5j847bee"/><path class="pr4dqmbxn"/><path class="n_d0zwbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:server-alert-20" {...props}></Icon>
