<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyfsf1tvs.css';
import '../../css/a/au3_lid1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyfsf1tvs secondary"/><path class="au3_lid1s primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-duo" {...props}></Icon>
