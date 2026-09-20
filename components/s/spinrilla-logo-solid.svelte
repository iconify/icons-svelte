<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at4gmo0jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="at4gmo0jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:spinrilla-logo-solid" {...props}></Icon>
