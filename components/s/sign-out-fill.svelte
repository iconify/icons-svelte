<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_kvtnbmk.css';
import '../../css/u/u3aficb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_kvtnbmk"/><path class="u3aficb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:sign-out-fill" {...props}></Icon>
