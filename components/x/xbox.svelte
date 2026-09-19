<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ued0hpkml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ued0hpkml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:xbox" {...props}></Icon>
