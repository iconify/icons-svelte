<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvvrcwmkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uvvrcwmkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:wallet-alt-01" {...props}></Icon>
