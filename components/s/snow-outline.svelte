<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f02eosw7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f02eosw7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:snow-outline" {...props}></Icon>
