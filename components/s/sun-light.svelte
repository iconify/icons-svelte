<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s709orkzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s709orkzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:sun-light" {...props}></Icon>
