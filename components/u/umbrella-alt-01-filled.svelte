<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyep2nb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyep2nb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:umbrella-alt-01-filled" {...props}></Icon>
