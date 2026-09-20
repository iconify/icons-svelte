<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgj4jib6k.css';
import '../../css/h/h5p52qoon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgj4jib6k"/><path class="h5p52qoon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:unix" {...props}></Icon>
