<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1km8wbhh.css';
import '../../css/g/gzxq6ibab.css';
import '../../css/a/ajxbbcbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1km8wbhh"/><path class="gzxq6ibab"/><path class="ajxbbcbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:smartphone-duotone" {...props}></Icon>
