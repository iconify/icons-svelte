<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8d273bat.css';
import '../../css/b/b81mgxb0y.css';
import '../../css/y/y8nlgsb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8d273bat"/><path class="b81mgxb0y"/><path class="y8nlgsb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tennis-bold" {...props}></Icon>
