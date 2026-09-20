<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecdu1dgna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ecdu1dgna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zabbix-dark" {...props}></Icon>
