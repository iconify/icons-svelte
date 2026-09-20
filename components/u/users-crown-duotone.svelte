<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcna0htye.css';
import '../../css/e/et2ofsb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcna0htye"/><path class="et2ofsb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:users-crown-duotone" {...props}></Icon>
