<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drabmdb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drabmdb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:voicemail-solid" {...props}></Icon>
