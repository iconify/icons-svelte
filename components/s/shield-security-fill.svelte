<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnr0hmy3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gnr0hmy3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:shield-security-fill" {...props}></Icon>
