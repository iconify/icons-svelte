<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eopkqoboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eopkqoboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-work-laptop-wifi-solid" {...props}></Icon>
