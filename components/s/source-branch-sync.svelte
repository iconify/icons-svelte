<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzb3qybbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzb3qybbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:source-branch-sync" {...props}></Icon>
