<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kss7hkagu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kss7hkagu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zabbix-light" {...props}></Icon>
