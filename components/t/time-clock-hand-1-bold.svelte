<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nellz_brh.css';
import '../../css/o/oubl2pb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nellz_brh"/><path class="oubl2pb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:time-clock-hand-1-bold" {...props}></Icon>
