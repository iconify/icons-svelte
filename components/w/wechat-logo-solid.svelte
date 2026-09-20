<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzpfmkbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bzpfmkbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wechat-logo-solid" {...props}></Icon>
