<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5dcexv3p.css';
import '../../css/j/jww6vuirk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5dcexv3p"/><path class="jww6vuirk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-cog" {...props}></Icon>
