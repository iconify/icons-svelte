<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axt6h9bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="axt6h9bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:speed-fill" {...props}></Icon>
