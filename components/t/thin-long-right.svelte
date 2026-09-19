<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7w644ytb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7w644ytb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:thin-long-right" {...props}></Icon>
