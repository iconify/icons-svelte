<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrdu5lrsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hrdu5lrsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:trashcan-solid-expressive" {...props}></Icon>
