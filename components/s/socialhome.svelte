<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y379_3lgr.css';
import '../../css/o/o774rzb4z.css';
import '../../css/x/xd1z83qkw.css';
import '../../css/v/vygt9fbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y379_3lgr"/><path class="o774rzb4z"/><path class="xd1z83qkw"/><path class="vygt9fbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:socialhome" {...props}></Icon>
