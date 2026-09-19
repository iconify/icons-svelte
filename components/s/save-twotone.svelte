<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udhx9jb5f.css';
import '../../css/v/vzilmrbae.css';
import '../../css/u/um7ec_bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="udhx9jb5f"/><path class="vzilmrbae"/><path class="um7ec_bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:save-twotone" {...props}></Icon>
