<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh7jieb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh7jieb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:ubuntu-logo-bold" {...props}></Icon>
