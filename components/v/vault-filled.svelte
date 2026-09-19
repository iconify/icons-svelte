<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an3z_3bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an3z_3bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:vault-filled" {...props}></Icon>
