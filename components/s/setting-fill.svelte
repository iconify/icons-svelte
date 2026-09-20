<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n02m407xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n02m407xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:setting-fill" {...props}></Icon>
