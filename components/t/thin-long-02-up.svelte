<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srlmpebxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srlmpebxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:thin-long-02-up" {...props}></Icon>
