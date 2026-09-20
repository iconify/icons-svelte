<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id-f7f-_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="id-f7f-_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:star" {...props}></Icon>
