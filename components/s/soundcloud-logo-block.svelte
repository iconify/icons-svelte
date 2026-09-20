<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d290v0skq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d290v0skq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:soundcloud-logo-block" {...props}></Icon>
