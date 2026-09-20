<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af8w4cc3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af8w4cc3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xvs" {...props}></Icon>
