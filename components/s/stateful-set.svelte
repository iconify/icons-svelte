<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyyeipb0v.css';
import '../../css/m/m8caoebdb.css';
import '../../css/c/cl10rdbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyyeipb0v"/><path class="m8caoebdb"/><path class="cl10rdbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:stateful-set" {...props}></Icon>
