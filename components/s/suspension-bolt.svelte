<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va8uaub1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="va8uaub1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:suspension-bolt" {...props}></Icon>
