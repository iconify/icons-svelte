<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6y9m7b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6y9m7b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:soundcloud-logo-bold" {...props}></Icon>
