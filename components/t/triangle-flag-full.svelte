<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li8dkqbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li8dkqbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:triangle-flag-full" {...props}></Icon>
