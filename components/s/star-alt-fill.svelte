<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y51pbhb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y51pbhb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:star-alt-fill" {...props}></Icon>
