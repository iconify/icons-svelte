<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sim9l-hfg.css';
import '../../css/e/emjhpkb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sim9l-hfg"/><path class="emjhpkb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:signout-alt-duotone" {...props}></Icon>
