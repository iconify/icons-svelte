<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf1wx9bka.css';
import '../../css/s/s6yt05ruj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="pf1wx9bka"/><path class="s6yt05ruj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-alt-fill" {...props}></Icon>
