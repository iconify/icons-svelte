<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qykhkv9au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qykhkv9au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:source-commit-end-local" {...props}></Icon>
