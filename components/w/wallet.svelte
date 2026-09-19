<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-8yqkjzv.css';
import '../../css/u/u3odm3brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-8yqkjzv"/><path class="u3odm3brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:wallet" {...props}></Icon>
