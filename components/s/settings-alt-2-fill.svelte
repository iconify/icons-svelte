<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euj3uvbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="euj3uvbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:settings-alt-2-fill" {...props}></Icon>
