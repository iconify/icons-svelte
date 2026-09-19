<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mozh4tbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mozh4tbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-pi-fill" {...props}></Icon>
