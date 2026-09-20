<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpmn_2k3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gpmn_2k3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:telegram-logo-1-block" {...props}></Icon>
