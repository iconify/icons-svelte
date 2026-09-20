<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quiooc0jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="quiooc0jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volume-loud-outline" {...props}></Icon>
