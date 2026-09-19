<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y46s7bv9m.css';
import '../../css/q/qo2zlmuak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y46s7bv9m"/><path class="qo2zlmuak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:twitch" {...props}></Icon>
