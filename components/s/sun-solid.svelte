<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp4_c_vog.css';
import '../../css/p/pswt3mbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp4_c_vog"/><path clip-rule="evenodd" class="pswt3mbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:sun-solid" {...props}></Icon>
