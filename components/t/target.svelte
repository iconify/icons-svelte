<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvzhpnn4z.css';
import '../../css/l/ljp4sfbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvzhpnn4z"/><path class="ljp4sfbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:target" {...props}></Icon>
