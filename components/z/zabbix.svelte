<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrn8gobul.css';
import '../../css/d/dp_5ikbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="wrn8gobul"/><path class="dp_5ikbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zabbix" {...props}></Icon>
