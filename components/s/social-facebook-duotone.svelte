<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxox9ob4e.css';
import '../../css/c/cnvf9lbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zxox9ob4e"/><path class="cnvf9lbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:social-facebook-duotone" {...props}></Icon>
